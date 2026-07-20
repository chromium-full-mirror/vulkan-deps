# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a0b513644803358f66ea6379e5d206963835afac',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'f47e9a7457c6c5e5a4bacfb47003be3e0daef252',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '29981f65241605e08b0ede4cfeb999fe3b723c6a',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '0d6fd73ca73830ccab5fa1f00ed5ed40124e2c55',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'e3b1eec08173d6b825cd3ac88c885a63b621504a',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '5f157b62e333c63260d05d81bf66faa216ab0fb8',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '286299bb6b732e4b22771cfb9d7d421542d40501',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'c279fa4350059faac3d2365df0538977e7e5b097',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'b73c06d337bb2c9e22b70e81ad0caecaf4d7f468',
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
