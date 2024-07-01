# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '33c7e30860928bab3819c3abae8297b109a02f73',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '00c49e3b56cc9748228d2e5b0d1e8e9c4409a02f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '2acb319af38d43be3ea76bfabf3998e5281d8d12',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c91d9ec1580dce89b10b0ca6a368800e2deaf1cb',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '190d2cb24e90e5bf2bec0a75604a9b3586485b6d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '36bf8bb4aa7220254385de704775fe982eea5ecf',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a3b0dae2528425de20965ca7a11a2e3086575956',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'df78ee39d2ff6c10b4f7f2ae06c7ca64524f9e25',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '2d13d34909e375e1850e6eaf8860052b9764656b',
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
