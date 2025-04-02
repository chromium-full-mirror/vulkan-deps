# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e57f993cff981c8c3ffd38967e030f04d13781a9',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '7a17be497c65ec897d8ce0ec5496e99be3e4d5fe',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '8e82b7cfeca98baae9a01a53511483da7194f854',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6add4e478f8802d3bbd100120e5ffc6f725ec9fe',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2ac81691baf291e7f4aad07596d7073974dbc4dd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '723d6b4aa35853315c6e021ec86388b3a2559fae',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '289efccc7560f2b970e2b4e0f50349da87669311',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '551221d913cc56218fcaddce086ae293d375ac28',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '508c50a69eab719e630323766afb0d49d7a780b7',
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
