# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'f6652dcf751920b1fbc132619b0e84ef3d6e77c4',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '6aba93196c86c82e8ebe50920876ae5c028acd9b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'a5164829e8f0255392c481696b63763a5e80be3c',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'b9997dafc791634ce51f6bed7ab886ea0e600a15',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '33d7f512583b8de44d1b6384aa1cf482f92e53e9',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '385716f0a63fe2c26e54a5140c9877a80da66592',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'faf69f66f2d9ba782fe37cabd19b9742f9f62eb3',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'a1e45945b3a84140956dc4672684090cf8e636a4',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6f5b5a4b034768139ff4fd1d797f6955d16e0f86',
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
