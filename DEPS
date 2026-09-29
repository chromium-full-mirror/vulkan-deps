# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'c0e1dbb69ac53f77102d813844f235fbf00776f3',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '98254945250cdf47d66779d427bed964071d7271',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'cb42dec3830d3ac67fa449ecdc0c0f73d5e74498',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '19e35eae1ab1574f31704ac002d77cbad6a064aa',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3c65a01745e4a1134d32b9c2c456472212dba16d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '4f7a5ef4749671d0dd2c9b73e99ca86e6b784fa5',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '69ca4d4b6590ab32e7a398725bfc90f81e6338e6',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '666fdaa0f87b9d49ae576473227b4b4cf428ba7e',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9509608ad38e5fda45942514a0865d6ae4c58eb5',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
